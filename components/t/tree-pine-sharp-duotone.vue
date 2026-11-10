<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eho5s_boo"/><path class="goi-6hb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tree-pine-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eho5s_boo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.942 1C12.239 1 12.57 1.13 12.76 1.36L17.767 7.36C18.015 7.66 18.068 8.07 17.904 8.42C17.759 8.73 17.396 8.95 17.066 9H16.076L18.78 12.37C19.02 12.68 19.066 13.09 18.9 13.43C18.754 13.74 18.399 13.95 18.073 14H16.409L19.707 17.29C19.993 17.58 20.079 18.01 19.924 18.38C19.788 18.71 19.421 18.95 19.077 19H4.98C4.626 19 4.263 18.75 4.084 18.45C3.929 18.08 3.986 17.58 4.272 17.29L7.569 14H5.981C5.597 14 5.247 13.78 5.08 13.43C4.913 13.09 4.959 12.68 5.199 12.37L7.903 9H6.983C6.595 9 6.241 8.78 6.076 8.42C5.912 8.07 5.964 7.66 6.212 7.36L11.244 1.33C11.406 1.17 11.719 1.02 11.942 1Z");
}

.goi-6hb-j {
  d: path("M12.991 18V23H10.988V18H12.991Z");
}

</style>
