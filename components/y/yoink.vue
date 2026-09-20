<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec7pwm9zi.css';
import '../../css/w/wdns3gx2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec7pwm9zi"/><path class="wdns3gx2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yoink" /></template>
