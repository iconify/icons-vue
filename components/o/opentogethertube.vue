<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9sl7lbit.css';
import '../../css/x/x7rph2bhw.css';
import '../../css/t/tx-4f1bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9sl7lbit"/><path class="x7rph2bhw"/><path class="tx-4f1bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentogethertube" /></template>
