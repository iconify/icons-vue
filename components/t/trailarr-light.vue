<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqyns6bnn.css';
import '../../css/n/nt61mgt6m.css';
import '../../css/o/om4uewb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqyns6bnn"/><path class="nt61mgt6m"/><path class="om4uewb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trailarr-light" /></template>
