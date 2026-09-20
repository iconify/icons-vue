<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2g407byi.css';
import '../../css/m/m7wldfb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2g407byi"/><path class="m7wldfb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unread-24" /></template>
