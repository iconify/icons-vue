<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm_sfu09j.css';
import '../../css/t/ti95e2suf.css';
import '../../css/r/rkysbabwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm_sfu09j"/><path class="ti95e2suf"/><path class="rkysbabwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:wine" /></template>
