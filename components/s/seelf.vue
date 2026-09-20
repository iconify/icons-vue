<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjyyrubdb.css';
import '../../css/l/l0tnl8bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjyyrubdb"/><path class="l0tnl8bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seelf" /></template>
