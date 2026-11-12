<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdzw-5b-o.css';
import '../../css/c/cargn6b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdzw-5b-o"/><path class="cargn6b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oneuptime" /></template>
