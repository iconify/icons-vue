<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1s3gobgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1s3gobgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:simple-icons" /></template>
