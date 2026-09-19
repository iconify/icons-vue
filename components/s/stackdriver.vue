<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhvsifbll.css';
import '../../css/k/kwokvsbhf.css';
import '../../css/o/oli25tbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhvsifbll"/><path class="kwokvsbhf"/><path class="oli25tbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:stackdriver" /></template>
