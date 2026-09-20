<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw6hy-k3l.css';
import '../../css/q/q7cxp6bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pw6hy-k3l"/><path clip-rule="evenodd" class="q7cxp6bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:safari-solid" /></template>
