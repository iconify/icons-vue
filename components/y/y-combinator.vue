<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkwx14bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkwx14bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:y-combinator" /></template>
