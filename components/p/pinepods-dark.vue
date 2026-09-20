<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc50gibdd.css';
import '../../css/v/v691k0tbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rc50gibdd"/><path clip-rule="evenodd" class="v691k0tbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinepods-dark" /></template>
