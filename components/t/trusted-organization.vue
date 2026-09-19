<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2yx2bcgg.css';
import '../../css/u/urz-4cihd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2yx2bcgg"/><circle class="urz-4cihd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:trusted-organization" /></template>
