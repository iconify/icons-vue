<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzeq6nw0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzeq6nw0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rows-two-filled" /></template>
