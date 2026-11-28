<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o35t1o4jt"/><path clip-rule="evenodd" class="mndk5hvdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-user-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mndk5hvdz {
  fill-rule: evenodd;
  d: path("M14.121 11.1213C13.579 11.6631 12.828 12 12 12C10.343 12 9 10.6569 9 9C9 7.3432 10.343 6 12 6C13.657 6 15 7.3432 15 9C15 9.8282 14.663 10.5795 14.121 11.1213ZM6 20V19C6 16.2386 8.239 14 11 14H13C15.761 14 18 16.2386 18 19V20H6Z");
}

.o35t1o4jt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H18C20.209 2 22 3.7909 22 6V18C22 20.2092 20.209 22 18 22H6C3.791 22 2 20.2092 2 18V6C2 3.7909 3.791 2 6 2H12Z");
}

</style>
