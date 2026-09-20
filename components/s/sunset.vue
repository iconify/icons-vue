<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3q1qbjn.css';
import '../../css/d/ds65nt-eh.css';
import '../../css/q/qvl9c6b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq3q1qbjn"/><path clip-rule="evenodd" class="ds65nt-eh"/><path class="qvl9c6b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sunset" /></template>
