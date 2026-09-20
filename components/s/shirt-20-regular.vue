<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f5danrfmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shirt-20-regular" /></template>
<style>
.f5danrfmv {
  fill: currentColor;
  d: path("M12.273 3.055a.5.5 0 0 1 .413-.019l4.627 1.85a1 1 0 0 1 .614 1.093l-.364 2.185a1 1 0 0 1-.987.836H15v7.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V9H3.424a1 1 0 0 1-.986-.836l-.365-2.185a1 1 0 0 1 .615-1.092l4.626-1.85l.103-.03a.5.5 0 0 1 .568.372C8.127 3.946 8.735 5 10 5s1.873-1.054 2.015-1.621a.5.5 0 0 1 .258-.324m.517 1.098C12.413 4.96 11.554 6 10 6S7.586 4.96 7.209 4.153l-4.15 1.661L3.425 8H5.5a.5.5 0 0 1 .5.5V16h8V8.5a.5.5 0 0 1 .5-.5h2.076l.364-2.186z");
}

</style>
