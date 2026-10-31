<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlsrw1b-f.css';
import '../../css/l/lmk6h0bvk.css';
import '../../css/m/m8y_5gyeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="qlsrw1b-f"/><path class="lmk6h0bvk"/><path class="m8y_5gyeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:thailand" /></template>
