<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahv9aqb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahv9aqb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:yoto" /></template>
