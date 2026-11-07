<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaizi48jf.css';
import '../../css/t/ty867ghkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaizi48jf"/><path class="ty867ghkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minus-bold-duotone" /></template>
