<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4ll1_buo.css';
import '../../css/v/vd6phjbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e4ll1_buo"/><path class="vd6phjbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:top-right" /></template>
