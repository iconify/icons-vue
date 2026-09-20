<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_sn15ygy.css';
import '../../css/s/sq7yslbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_sn15ygy"/><path class="sq7yslbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:material-for-mkdocs-dark" /></template>
