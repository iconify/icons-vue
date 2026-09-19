<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_acv7bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="b_acv7bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:roadtunnel" /></template>
