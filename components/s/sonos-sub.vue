<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsym9qk0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsym9qk0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sonos-sub" /></template>
