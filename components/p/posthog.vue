<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbssek_nw.css';
import '../../css/p/pv56n73nc.css';
import '../../css/a/a47dmxbwp.css';
import '../../css/p/pkcocdbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vbssek_nw"/><path class="pv56n73nc"/><path class="a47dmxbwp"/><path class="pkcocdbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posthog" /></template>
