<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/socnatb_v.css';
import '../../css/o/oyw6nnb2s.css';
import '../../css/x/xh-ojeezs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="socnatb_v"/><path class="oyw6nnb2s"/><path class="xh-ojeezs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:martinique" /></template>
