<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrl-cic7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="zrl-cic7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:padlock-alt-f" /></template>
