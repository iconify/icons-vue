<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc_p1acct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vc_p1acct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:standard-notes-light" /></template>
