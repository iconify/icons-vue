<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1nge984c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1nge984c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror-filled" /></template>
