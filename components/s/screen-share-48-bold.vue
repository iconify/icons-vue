<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw2mmrfxt.css';
import '../../css/p/phox42bnd.css';
import '../../css/q/qh1-sxi6o.css';
import '../../css/k/kn0wafhon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw2mmrfxt"/><path class="phox42bnd"/><path class="qh1-sxi6o"/><path class="kn0wafhon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screen-share-48-bold" /></template>
