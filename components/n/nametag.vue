<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he0w76bjd.css';
import '../../css/n/n3c1i_dav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="he0w76bjd"/><path class="n3c1i_dav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nametag" /></template>
