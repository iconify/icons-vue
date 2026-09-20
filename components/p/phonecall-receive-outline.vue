<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr1bbeb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cr1bbeb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:phonecall-receive-outline" /></template>
