<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc7cgqb6v.css';
import '../../css/r/r24iznqrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc7cgqb6v"/><path class="r24iznqrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:send-email-fly" /></template>
