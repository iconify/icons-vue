<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lscw_8blz.css';
import '../../css/c/cgqm05v5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lscw_8blz"/><path class="cgqm05v5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reclaimerr-light" /></template>
