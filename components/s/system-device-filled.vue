<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdrep3bvl.css';
import '../../css/z/zth91qbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdrep3bvl"/><path class="zth91qbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-device-filled" /></template>
