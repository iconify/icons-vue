<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_f1tn5f.css';
import '../../css/g/gj0rcw2bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_f1tn5f"/><path class="gj0rcw2bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-bold-duotone" /></template>
