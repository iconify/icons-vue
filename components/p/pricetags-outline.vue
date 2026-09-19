<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neoc4fbwo.css';
import '../../css/u/ui33wlb3m.css';
import '../../css/m/midf3bbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="neoc4fbwo"/><path class="ui33wlb3m"/><path class="midf3bbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pricetags-outline" /></template>
