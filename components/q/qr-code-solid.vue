<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v73rypy0t.css';
import '../../css/d/dp85ht2pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v73rypy0t"/><path class="dp85ht2pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:qr-code-solid" /></template>
