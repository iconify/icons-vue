<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faxt378lm.css';
import '../../css/e/ezv3-gbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="faxt378lm"/><path class="ezv3-gbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onwatch" /></template>
