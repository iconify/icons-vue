<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzejkebtm.css';
import '../../css/k/kjmdvfbaw.css';
import '../../css/j/jxve6plzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzejkebtm"/><path class="kjmdvfbaw"/><path class="jxve6plzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:milkomeda-c1" /></template>
