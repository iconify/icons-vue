<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fys4zfbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fys4zfbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ginetex:professional-care" /></template>
