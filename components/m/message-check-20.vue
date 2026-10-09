<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh8pb8bip.css';
import '../../css/i/iq88sthgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xh8pb8bip"/><path class="iq88sthgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-check-20" /></template>
