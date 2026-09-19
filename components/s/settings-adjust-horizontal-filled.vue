<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk0s61b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk0s61b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:settings-adjust-horizontal-filled" /></template>
