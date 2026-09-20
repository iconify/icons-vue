<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geedsobpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="geedsobpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yeetfile-light" /></template>
