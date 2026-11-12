<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ctizbcx.css';
import '../../css/m/m8et6-xvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6ctizbcx"/><path class="m8et6-xvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roundcube-dark" /></template>
