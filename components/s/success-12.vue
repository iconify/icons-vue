<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svsuljcxx.css';
import '../../css/c/ck8dpqbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="svsuljcxx"/><path clip-rule="evenodd" class="ck8dpqbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:success-12" /></template>
