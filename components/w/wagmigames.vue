<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3-5_c46r.css';
import '../../css/f/fgtzzk1mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3-5_c46r"/><path class="fgtzzk1mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wagmigames" /></template>
