<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzhi-ac4k.css';
import '../../css/c/ck99yo6hz.css';
import '../../css/g/gqyaulbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzhi-ac4k"/><path class="ck99yo6hz"/><path class="gqyaulbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-light" /></template>
