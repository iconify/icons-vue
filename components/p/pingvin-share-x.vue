<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ky4jnzf.css';
import '../../css/j/jlozx9b3a.css';
import '../../css/w/wdip6sk2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="s3ky4jnzf"/><path class="jlozx9b3a"/><path class="wdip6sk2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pingvin-share-x" /></template>
