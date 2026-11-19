<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo29c561l.css';
import '../../css/i/iaayajjtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wo29c561l"/><path class="iaayajjtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scryer-dark" /></template>
