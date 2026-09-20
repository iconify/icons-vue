<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhipymbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhipymbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-waves" /></template>
