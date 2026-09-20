<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-51v_02i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-51v_02i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:unlink-2" /></template>
