<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc10j4kob.css';
import '../../css/t/tw4lkvbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc10j4kob"/><path class="tw4lkvbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:microphone-solid" /></template>
