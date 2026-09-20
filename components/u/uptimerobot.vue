<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5lz9no8r.css';
import '../../css/b/b5b9_cc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a5lz9no8r"/><circle class="b5b9_cc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimerobot" /></template>
