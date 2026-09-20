<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kljix3b2j.css';
import '../../css/g/gb6l_zk0s.css';
import '../../css/b/bbjq83b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kljix3b2j"/><path class="gb6l_zk0s"/><path class="bbjq83b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailpit" /></template>
