<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5idgqqvy.css';
import '../../css/b/b2ubuucrp.css';
import '../../css/q/qfey2lb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b5idgqqvy"/><path class="b2ubuucrp"/><path class="qfey2lb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-outgoing-48-bold" /></template>
