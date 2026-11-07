<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9y477w0i.css';
import '../../css/w/wwbiboy9e.css';
import '../../css/b/bykm3gk0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="wwbiboy9e"/><path class="bykm3gk0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-zoom-out-bold-duotone" /></template>
