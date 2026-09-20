<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v326h-n7o.css';
import '../../css/r/rc04i3pkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v326h-n7o"/><path class="rc04i3pkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planarally" /></template>
