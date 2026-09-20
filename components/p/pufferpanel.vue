<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m21fiubni.css';
import '../../css/j/j3h0ykbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m21fiubni"/><path class="j3h0ykbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pufferpanel" /></template>
