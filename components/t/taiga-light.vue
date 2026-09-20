<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s90tedchv.css';
import '../../css/j/jdpagb2-o.css';
import '../../css/m/mam2srhpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s90tedchv"/><path class="jdpagb2-o"/><path class="mam2srhpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:taiga-light" /></template>
