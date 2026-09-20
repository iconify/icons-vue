<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b578igxdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b578igxdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wave-bye-filled" /></template>
