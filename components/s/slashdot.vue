<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6vo45b0z.css';
import '../../css/z/z5rc_zbev.css';
import '../../css/g/glg2zcb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6vo45b0z"/><path class="z5rc_zbev"/><path class="glg2zcb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slashdot" /></template>
