<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo2kww2oc.css';
import '../../css/m/mnb9ye_jk.css';
import '../../css/i/i3ywqmbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo2kww2oc wm-k"/><path class="mnb9ye_jk wm-k"/><path class="i3ywqmbxr wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:refrigerator" /></template>
