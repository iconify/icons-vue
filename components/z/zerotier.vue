<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv_3wkq1r.css';
import '../../css/w/wisf880rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kv_3wkq1r"/><path class="wisf880rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zerotier" /></template>
