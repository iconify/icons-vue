<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxd_hdc6p.css';
import '../../css/l/l4_6mubqz.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 xxd_hdc6p"/><path class="clr-i-solid clr-i-solid-path-2 l4_6mubqz"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:thumbs-up-solid" /></template>
