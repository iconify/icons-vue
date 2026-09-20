<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckjv9dbko.css';
import '../../css/h/h35m5hcqe.css';
import '../../css/z/ztgnliu0b.css';
import '../../css/k/kd94m1b4e.css';
import '../../css/m/mdpqnwn5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ckjv9dbko"/><path class="h35m5hcqe"/><path class="ztgnliu0b"/><path class="kd94m1b4e"/><path class="mdpqnwn5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:undb" /></template>
