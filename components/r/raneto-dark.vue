<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc19hobba.css';
import '../../css/g/gd6c7lbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kc19hobba"/><path class="gd6c7lbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raneto-dark" /></template>
