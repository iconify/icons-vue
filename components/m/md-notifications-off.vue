<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk4gz-bbp.css';
import '../../css/a/afn_zrbzk.css';
import '../../css/v/vcstj9lyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk4gz-bbp"/><path class="afn_zrbzk"/><path class="vcstj9lyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-notifications-off" /></template>
