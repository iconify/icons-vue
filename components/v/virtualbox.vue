<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow53i4btd.css';
import '../../css/j/jz3gn8btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow53i4btd"/><path class="jz3gn8btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:virtualbox" /></template>
