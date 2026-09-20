<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw5h8ln7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw5h8ln7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:save-24" /></template>
