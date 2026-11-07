<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_f1tn5f.css';
import '../../css/n/n4onjj4ki.css';
import '../../css/d/dxbitbv-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_f1tn5f"/><path class="n4onjj4ki"/><path class="dxbitbv-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-add-bold-duotone" /></template>
