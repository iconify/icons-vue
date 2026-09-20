<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1yjti6ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1yjti6ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:social-media-logo" /></template>
