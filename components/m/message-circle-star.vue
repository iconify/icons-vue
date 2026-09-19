<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu72iwgtz.css';
import '../../css/m/myfc5_k7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu72iwgtz"/><path class="myfc5_k7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-star" /></template>
