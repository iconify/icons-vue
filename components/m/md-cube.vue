<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjnbpgbsn.css';
import '../../css/f/fd5cwebhy.css';
import '../../css/h/h5uul4bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjnbpgbsn"/><path class="fd5cwebhy"/><path class="h5uul4bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cube" /></template>
