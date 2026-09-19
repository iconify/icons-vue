<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb5dzpbru.css';
import '../../css/h/h8kldlbhr.css';
import '../../css/c/cxd7u3b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb5dzpbru"/><path class="h8kldlbhr"/><path class="cxd7u3b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:nomouth" /></template>
