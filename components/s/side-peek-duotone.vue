<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq_t1dwcz.css';
import '../../css/d/deu3b0kil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq_t1dwcz"/><path class="deu3b0kil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:side-peek-duotone" /></template>
