<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i2ew1ke.css';
import '../../css/m/m8lmgdacv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path class="m8lmgdacv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:refresh" /></template>
