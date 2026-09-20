<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb87fub2m.css';
import '../../css/i/igrgcsw-i.css';
import '../../css/a/ak8i1tnjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nb87fub2m"/><path class="igrgcsw-i"/><path class="ak8i1tnjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netgear-dark" /></template>
