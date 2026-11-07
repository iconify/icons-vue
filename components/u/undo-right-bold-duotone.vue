<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp69ui1wu.css';
import '../../css/f/f63v77q_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wp69ui1wu"/><path class="f63v77q_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-bold-duotone" /></template>
