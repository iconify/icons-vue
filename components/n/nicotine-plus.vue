<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amp1qmb0a.css';
import '../../css/s/sgi4nb-bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amp1qmb0a"/><path class="sgi4nb-bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nicotine-plus" /></template>
