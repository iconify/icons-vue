<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfo1tsbjl.css';
import '../../css/p/pz67xgbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfo1tsbjl"/><path class="pz67xgbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:patio-filled" /></template>
