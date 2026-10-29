<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkcjtgbqv.css';
import '../../css/s/s9b9x4b1t.css';
import '../../css/v/vysl2zzjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkcjtgbqv wm-k"/><path class="s9b9x4b1t wm-a"/><path class="vysl2zzjq wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:map" /></template>
