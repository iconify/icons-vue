<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6z_s2t8r.css';
import '../../css/n/n828ekbgf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 l6z_s2t8r"/><circle class="clr-i-solid clr-i-solid-path-2 n828ekbgf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:user-solid" /></template>
