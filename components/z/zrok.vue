<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boq6ejbul.css';
import '../../css/z/zlg69lb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="boq6ejbul"/><path class="zlg69lb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zrok" /></template>
