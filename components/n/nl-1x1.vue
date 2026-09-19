<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbx2t-b6x.css';
import '../../css/a/aw9rmcz9o.css';
import '../../css/x/xyokvnbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbx2t-b6x"/><path class="aw9rmcz9o"/><path class="xyokvnbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:nl-1x1" /></template>
