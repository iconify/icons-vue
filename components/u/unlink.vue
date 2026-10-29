<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxry_0vvk.css';
import '../../css/e/easy1lbny.css';
import '../../css/a/a_-wkp7vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yxry_0vvk"/><path class="easy1lbny wm-k"/><path class="a_-wkp7vc wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:unlink" /></template>
