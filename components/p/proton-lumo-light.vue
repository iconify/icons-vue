<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5my-u8du.css';
import '../../css/a/atca9c2ie.css';
import '../../css/t/tp4af3bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5my-u8du"/><path class="atca9c2ie"/><path class="tp4af3bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-lumo-light" /></template>
