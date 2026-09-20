<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1njp3l4b.css';
import '../../css/m/md6xbkbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1njp3l4b"/><path class="md6xbkbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:moon-waxing-crescent" /></template>
