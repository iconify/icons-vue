<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/relf4wlgz.css';
import '../../css/v/vlm33lmng.css';
import '../../css/s/snp287xku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="relf4wlgz"/><path class="vlm33lmng"/><path class="snp287xku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:turkey" /></template>
