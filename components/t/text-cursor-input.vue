<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy05ngn_w.css';
import '../../css/r/r76_vnpan.css';
import '../../css/b/b3q0u7byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy05ngn_w wm-k"/><path class="r76_vnpan wm-a"/><path class="b3q0u7byj wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:text-cursor-input" /></template>
