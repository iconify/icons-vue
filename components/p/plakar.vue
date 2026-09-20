<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2zp5lmjm.css';
import '../../css/s/sx1z59bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2zp5lmjm"/><path class="sx1z59bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plakar" /></template>
