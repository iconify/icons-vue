<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/y/y7ma373nd.css';
import '../../css/g/go4rm8bar.css';
import '../../css/p/pydsljbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="y7ma373nd"/><path class="go4rm8bar"/><path class="pydsljbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smile-circle-bold-duotone" /></template>
