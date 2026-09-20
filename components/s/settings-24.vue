<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfpnljbdr.css';
import '../../css/r/rmabd8pvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfpnljbdr"/><path clip-rule="evenodd" class="rmabd8pvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:settings-24" /></template>
