<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiz4a2b8e.css';
import '../../css/n/nklbxtbfr.css';
import '../../css/s/shtujqapo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iiz4a2b8e"/><circle class="nklbxtbfr"/><path class="shtujqapo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:suwayomi-dark" /></template>
