<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpt2i3bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpt2i3bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:person-planet-earth" /></template>
