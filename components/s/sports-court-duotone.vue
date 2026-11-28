<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ybks3jbup"/><path clip-rule="evenodd" class="lf3w-pbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sports-court-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lf3w-pbuw {
  fill-rule: evenodd;
  d: path("M13 3V4V9.171C14.165 9.582 15 10.694 15 12C15 12.828 14.663 13.58 14.121 14.121C13.809 14.434 13.427 14.678 13 14.829V20V21H11V20V14.829C9.835 14.417 9 13.306 9 12C9 10.694 9.835 9.582 11 9.171V4V3H12H13ZM1 7H2H5C5.552 7 6.053 7.225 6.414 7.586C6.775 7.947 7 8.448 7 9V15C7 15.552 6.775 16.053 6.414 16.414C6.053 16.775 5.552 17 5 17H2H1V15H2H5V9H2H1V7ZM23 9H22H19V15H22H23V17H22H19C18.448 17 17.947 16.775 17.586 16.414C17.225 16.053 17 15.552 17 15V9C17 8.448 17.225 7.947 17.586 7.586C17.947 7.225 18.448 7 19 7H22H23V9ZM12 11C11.448 11 11 11.448 11 12C11 12.552 11.448 13 12 13C12.276 13 12.525 12.889 12.707 12.707C12.889 12.525 13 12.276 13 12C13 11.448 12.552 11 12 11Z");
}

.ybks3jbup {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3H19C21.209 3 23 4.791 23 7V17C23 19.209 21.209 21 19 21H5C2.791 21 1 19.209 1 17V7C1 4.791 2.791 3 5 3H12Z");
}

</style>
