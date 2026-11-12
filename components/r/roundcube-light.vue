<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc26ied2w.css';
import '../../css/z/zrv1yxb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jc26ied2w"/><path class="zrv1yxb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roundcube-light" /></template>
