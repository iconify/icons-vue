<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuz81zbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="vuz81zbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:slaughterhouse-11" /></template>
