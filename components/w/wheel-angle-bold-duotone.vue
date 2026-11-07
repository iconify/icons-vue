<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se4__r1yu.css';
import '../../css/j/jbg5enbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="se4__r1yu"/><path class="jbg5enbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-angle-bold-duotone" /></template>
