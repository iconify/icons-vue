<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svidcsblb.css';
import '../../css/v/v744t56bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="svidcsblb"/><path class="v744t56bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voidauth-dark" /></template>
