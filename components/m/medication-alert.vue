<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfm1etoml.css';
import '../../css/t/tg8jb6oai.css';
import '../../css/f/fdrpmfhbn.css';
import '../../css/o/og4dv3brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mfm1etoml"/><path class="tg8jb6oai"/><circle class="fdrpmfhbn"/><path class="og4dv3brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:medication-alert" /></template>
