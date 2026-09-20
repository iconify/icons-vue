<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_9rqpxcs.css';
import '../../css/z/zc6vvbcxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_9rqpxcs"/><path class="zc6vvbcxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openadserver-light" /></template>
