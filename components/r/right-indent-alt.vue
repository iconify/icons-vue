<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbvrgpb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbvrgpb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:right-indent-alt" /></template>
