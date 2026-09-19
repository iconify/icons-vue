<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drkhbl8_m.css';
import '../../css/z/zyav6vbpo.css';
import '../../css/l/lfy2osnfb.css';
import '../../css/f/fgt9l6boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drkhbl8_m"/><path class="zyav6vbpo"/><path class="lfy2osnfb"/><path clip-rule="evenodd" class="fgt9l6boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:viber-outline" /></template>
