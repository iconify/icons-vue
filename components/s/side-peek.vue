<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkbgrjdet.css';
import '../../css/l/l9ksdwb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkbgrjdet"/><path clip-rule="evenodd" class="l9ksdwb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:side-peek" /></template>
