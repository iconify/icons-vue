<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da49kcg0i.css';
import '../../css/x/xdwstclco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da49kcg0i"/><path class="xdwstclco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:red-packet-fill" /></template>
