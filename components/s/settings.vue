<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7d-ndb_c.css';
import '../../css/g/gum_8r72e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><path class="gum_8r72e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:settings" /></template>
