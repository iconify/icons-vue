<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4e9tjb-p.css';
import '../../css/r/r33vs8zyw.css';
import '../../css/w/w7guu_23n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4e9tjb-p"/><path clip-rule="evenodd" class="r33vs8zyw"/><path class="w7guu_23n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sfm" /></template>
