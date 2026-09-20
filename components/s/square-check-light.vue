<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z--u7bblr.css';
import '../../css/k/kfpic71-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z--u7bblr"/><path class="kfpic71-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-check-light" /></template>
