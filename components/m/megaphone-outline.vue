<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8i4wsn-f.css';
import '../../css/g/gucvo3bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8i4wsn-f"/><path class="gucvo3bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:megaphone-outline" /></template>
