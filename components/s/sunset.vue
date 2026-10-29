<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjwqr1b2g.css';
import '../../css/h/hctk37wzh.css';
import '../../css/l/lid4jmbmv.css';
import '../../css/h/hr-ab2d5l.css';
import '../../css/u/uuzoueb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjwqr1b2g wm-k"/><path class="hctk37wzh wm-k"/><path class="lid4jmbmv wm-a"/><path class="hr-ab2d5l wm-s"/><path class="uuzoueb2e wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sunset" /></template>
